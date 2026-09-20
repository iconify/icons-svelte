<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr24jkwsh.css';
import '../../css/a/ao18k45ue.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/ducf-wbyw.css';
import '../../css/n/nhrj7sblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jr24jkwsh"/><path class="ao18k45ue"/><g class="ij2x_72vy"><path class="ducf-wbyw"/><path class="nhrj7sblw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orca" {...props}></Icon>
