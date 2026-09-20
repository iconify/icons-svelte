<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xub8gacdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":0,"height":0,"left":-28.989,"top":-29};
const content = `<path class="xub8gacdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:logitech-g" {...props}></Icon>
