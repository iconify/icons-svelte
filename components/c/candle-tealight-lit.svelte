<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u_x2yob8p.css';
import '../../css/y/ylhnziwri.css';
import '../../css/e/eazdbabko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u_x2yob8p"/><ellipse class="ylhnziwri"/><path class="eazdbabko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:candle-tealight-lit" {...props}></Icon>
