<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylolabndh.css';
import '../../css/c/c1x3yyvty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ylolabndh"/><path class="c1x3yyvty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-financial-sustainability-check" {...props}></Icon>
