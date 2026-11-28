<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a25g90ajj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/ss8t1tbbv.css';
import '../../css/g/g-jxrmkmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a25g90ajj secondary"/><g class="dt0cm9dhy primary"><path class="ss8t1tbbv"/><path class="g-jxrmkmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-x-duo" {...props}></Icon>
