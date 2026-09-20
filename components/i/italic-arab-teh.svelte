<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hulgzbbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hulgzbbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-arab-teh" {...props}></Icon>
