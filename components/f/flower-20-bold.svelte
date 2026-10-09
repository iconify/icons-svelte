<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv2u68byn.css';
import '../../css/h/hjfbf5arh.css';
import '../../css/u/uz5d7nbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wv2u68byn"/><path class="hjfbf5arh"/><path class="uz5d7nbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flower-20-bold" {...props}></Icon>
