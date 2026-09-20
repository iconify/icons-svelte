<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp00_mbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dp00_mbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-search" {...props}></Icon>
