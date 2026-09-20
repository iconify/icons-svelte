<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivl5r6cnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivl5r6cnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-check" {...props}></Icon>
