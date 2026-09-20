<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/funjsb_-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="funjsb_-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-a" {...props}></Icon>
