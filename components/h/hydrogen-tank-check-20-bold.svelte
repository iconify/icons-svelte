<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmp_5zpfe.css';
import '../../css/j/jj7ew2vkc.css';
import '../../css/k/k2ahn_bem.css';
import '../../css/e/e54bjx_0d.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmp_5zpfe"/><path class="jj7ew2vkc"/><path class="k2ahn_bem"/><path class="e54bjx_0d"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-tank-check-20-bold" {...props}></Icon>
