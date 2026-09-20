<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkb05-p-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vkb05-p-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-two-rtl" {...props}></Icon>
