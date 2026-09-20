<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrailb4ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zrailb4ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-k" {...props}></Icon>
