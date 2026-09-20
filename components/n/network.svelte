<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/feh9g0bqf.css';
import '../../css/p/pvotryzei.css';
import '../../css/k/k41zy7q4s.css';
import '../../css/e/en34xy1yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="feh9g0bqf"/><rect class="pvotryzei"/><rect class="k41zy7q4s"/><path class="en34xy1yh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:network" {...props}></Icon>
