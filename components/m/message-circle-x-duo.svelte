<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm28qqb4l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/v/vxv-_zzso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sm28qqb4l"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="vxv-_zzso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-x-duo" {...props}></Icon>
