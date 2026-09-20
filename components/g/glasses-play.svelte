<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xywp-lbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xywp-lbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:glasses-play" {...props}></Icon>
