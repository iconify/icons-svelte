<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq7dzc16m.css';
import '../../css/e/e_cwsjbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jq7dzc16m"/><path class="e_cwsjbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:road-weather" {...props}></Icon>
