<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1kn_kt2k.css';
import '../../css/v/vivtzcqvh.css';
import '../../css/p/p7a19mbmd.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/komkke12x.css';
import '../../css/y/y8sfjbbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u1kn_kt2k"/><path class="vivtzcqvh"/><path class="p7a19mbmd"/><g class="ij2x_72vy"><path class="komkke12x"/><path class="y8sfjbbfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pistol" {...props}></Icon>
