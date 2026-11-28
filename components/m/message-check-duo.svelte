<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm28qqb4l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/f/ffevkebrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sm28qqb4l"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="ffevkebrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-check-duo" {...props}></Icon>
