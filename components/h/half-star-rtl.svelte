<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lde70vbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lde70vbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:half-star-rtl" {...props}></Icon>
