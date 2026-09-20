<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oikpp_b-d.css';
import '../../css/a/a9mph4b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oikpp_b-d"/><path class="a9mph4b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-not-found-rtl" {...props}></Icon>
