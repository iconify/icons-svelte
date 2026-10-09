<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbe-aclic.css';
import '../../css/i/iv-96i7pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cbe-aclic"/><path class="iv-96i7pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cylinder-20" {...props}></Icon>
