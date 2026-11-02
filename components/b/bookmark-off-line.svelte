<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2s-3gbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2s-3gbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-off-line" {...props}></Icon>
