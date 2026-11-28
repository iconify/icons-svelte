<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u45dg3bwf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qeq7gbben.css';
import '../../css/j/jbsk87b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u45dg3bwf"/><g class="dt0cm9dhy primary"><path class="qeq7gbben"/><path class="jbsk87b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:airplay-duo" {...props}></Icon>
