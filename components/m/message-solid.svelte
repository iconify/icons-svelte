<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwf0qho5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwf0qho5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:message-solid" {...props}></Icon>
