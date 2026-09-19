<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk7_07bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dk7_07bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-noncommercial-us" {...props}></Icon>
