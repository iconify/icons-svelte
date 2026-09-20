<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycor5295j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ycor5295j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:health-medical-syringe-instrument-medical-syringe-health-beauty-needle" {...props}></Icon>
