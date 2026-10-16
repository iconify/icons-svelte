<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlg1icbmr.css';
import '../../css/r/res8m0bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xlg1icbmr"/><path class="res8m0bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boiler-20" {...props}></Icon>
