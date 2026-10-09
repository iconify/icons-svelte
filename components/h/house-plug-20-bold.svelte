<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coivkzecr.css';
import '../../css/f/fengbsb3f.css';
import '../../css/n/n1tbb-ujx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="fengbsb3f"/><path class="n1tbb-ujx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-plug-20-bold" {...props}></Icon>
