<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4g5aej_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4g5aej_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-ltr" {...props}></Icon>
