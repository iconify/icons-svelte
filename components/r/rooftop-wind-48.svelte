<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re15mubga.css';
import '../../css/r/rhjk9ujih.css';
import '../../css/j/jtbcv1bmm.css';
import '../../css/p/pfp2tbb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="re15mubga"/><path class="rhjk9ujih"/><path class="jtbcv1bmm"/><path class="pfp2tbb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rooftop-wind-48" {...props}></Icon>
