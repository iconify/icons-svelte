<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qua7fvb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qua7fvb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:four-of-circles-mahjong-filled" {...props}></Icon>
