<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1pz25ahp.css';
import '../../css/z/z0v5_fbef.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j1pz25ahp"/><path class="z0v5_fbef"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-paid-20-bold" {...props}></Icon>
