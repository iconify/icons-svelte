<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh-bxob0v.css';
import '../../css/o/or6tflh7g.css';
import '../../css/w/wt5q0gb-i.css';
import '../../css/i/i-zynpbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jh-bxob0v"/><path class="or6tflh7g"/><path class="wt5q0gb-i"/><path class="i-zynpbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:byparr" {...props}></Icon>
