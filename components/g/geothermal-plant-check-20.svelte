<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryuntyb6m.css';
import '../../css/d/d2zrzusbd.css';
import '../../css/y/yt1kjcbtq.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ryuntyb6m"/><path class="d2zrzusbd"/><path class="yt1kjcbtq"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-check-20" {...props}></Icon>
