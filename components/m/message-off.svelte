<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7w8xj34l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7w8xj34l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-off" {...props}></Icon>
