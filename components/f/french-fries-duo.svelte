<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppd78f9kg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dq3ueh2oc.css';
import '../../css/t/teh9ljbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppd78f9kg secondary"/><g class="dt0cm9dhy primary"><path class="dq3ueh2oc"/><path class="teh9ljbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:french-fries-duo" {...props}></Icon>
