<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u468jwmsc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cfhh0mbqp.css';
import '../../css/c/cm9o0sbya.css';
import '../../css/c/cdp9-zb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u468jwmsc"/><g class="dt0cm9dhy primary"><path class="cfhh0mbqp"/><path class="cm9o0sbya"/><path class="cdp9-zb2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-hail-duo" {...props}></Icon>
