<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl7-40bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zl7-40bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:four-of-circles-mahjong" {...props}></Icon>
