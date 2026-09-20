<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuzmv5bfi.css';
import '../../css/m/m3ckqtbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uuzmv5bfi"/><path class="m3ckqtbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:articles-search-rtl" {...props}></Icon>
