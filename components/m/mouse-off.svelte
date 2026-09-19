<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o76hf3z6x.css';
import '../../css/f/fvpfrkbjr.css';
import '../../css/n/n_-vh9kdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o76hf3z6x"/><path class="fvpfrkbjr"/><path class="n_-vh9kdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-off" {...props}></Icon>
