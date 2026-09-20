<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-ii8ac4d.css';
import '../../css/y/y0mw4ibgt.css';
import '../../css/i/im1hkobej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-ii8ac4d"/><path class="y0mw4ibgt"/><path class="im1hkobej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-minimalistic-broken" {...props}></Icon>
