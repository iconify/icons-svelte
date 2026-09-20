<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu85lyb9a.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/o-mn23hdo.css';
import '../../css/m/mtmqpmbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="fu85lyb9a"/><g class="ij2x_72vy"><circle class="o-mn23hdo"/><path class="mtmqpmbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:bright-button" {...props}></Icon>
