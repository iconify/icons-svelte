<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kawrq6d1m.css';
import '../../css/m/mjvs1cblk.css';
import '../../css/i/i81te_6rg.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/q/qpu-t5qeu.css';
import '../../css/d/defjnrbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kawrq6d1m"/><path class="mjvs1cblk"/><path class="i81te_6rg"/><g class="ij2x_72vy"><path class="qpu-t5qeu"/><path class="defjnrbmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:locked" {...props}></Icon>
