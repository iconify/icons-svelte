<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y49u1nbmf.css';
import '../../css/m/m8-2r70ks.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mwr3xccrq.css';
import '../../css/i/ie-7kriki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="y49u1nbmf"/><path class="m8-2r70ks"/><g class="ij2x_72vy"><path class="mwr3xccrq"/><path class="ie-7kriki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:honey-pot" {...props}></Icon>
