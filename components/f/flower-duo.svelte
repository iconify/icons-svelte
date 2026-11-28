<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8sggb0m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pxvp_ztez.css';
import '../../css/i/ij7qju6sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8sggb0m secondary"/><g class="dt0cm9dhy primary"><path class="pxvp_ztez"/><circle class="ij7qju6sg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flower-duo" {...props}></Icon>
