<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm28qqb4l.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/h/hzekqp9bo.css';
import '../../css/v/vmum7ebuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sm28qqb4l"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="hzekqp9bo"/><path class="vmum7ebuf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-question-duo" {...props}></Icon>
