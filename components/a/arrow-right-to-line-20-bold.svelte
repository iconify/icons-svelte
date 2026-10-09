<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvilsvvcy.css';
import '../../css/d/d6ukndv1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bvilsvvcy"/><path class="d6ukndv1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-to-line-20-bold" {...props}></Icon>
