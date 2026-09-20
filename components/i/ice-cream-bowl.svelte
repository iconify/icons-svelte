<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/g5_mh2foo.css';
import '../../css/u/uxko0ibmv.css';
import '../../css/h/h054lbbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g5_mh2foo"/><path class="uxko0ibmv"/><path class="h054lbbok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ice-cream-bowl" {...props}></Icon>
