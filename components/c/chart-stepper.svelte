<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqgem5-dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fqgem5-dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-stepper" {...props}></Icon>
