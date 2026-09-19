<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z85e-1boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z85e-1boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:one-of-circles-mahjong-filled" {...props}></Icon>
