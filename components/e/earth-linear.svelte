<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y-ioddvys.css';
import '../../css/y/y44uunbxa.css';
import '../../css/u/uvx097b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y-ioddvys"/><path class="y44uunbxa"/><path class="uvx097b-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-linear" {...props}></Icon>
