<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-iaqv3wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y-iaqv3wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-geor-kan" {...props}></Icon>
