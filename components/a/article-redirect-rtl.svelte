<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2kzi90wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2kzi90wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-redirect-rtl" {...props}></Icon>
