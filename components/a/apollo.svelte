<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ex-9i5bwz.css';
import '../../css/i/ibq7yybfi.css';
import '../../css/g/gbpgd7ber.css';
import '../../css/s/si0gkjbfl.css';
import '../../css/v/vry884blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect fill="url(#SVG5n3uCcuF)" class="ex-9i5bwz"/><path class="ibq7yybfi"/><path class="gbpgd7ber"/><defs><linearGradient id="SVG5n3uCcuF" x1="0" x2="256" y1="0" y2="256" gradientUnits="userSpaceOnUse"><stop class="si0gkjbfl"/><stop offset="1" class="vry884blf"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:apollo" {...props}></Icon>
