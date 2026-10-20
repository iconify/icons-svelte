<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rp5kndbph.css';
import '../../css/o/oln7pibrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rp5kndbph"/><path class="oln7pibrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pin-house" {...props}></Icon>
