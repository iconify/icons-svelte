<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjeh93b6f.css';
import '../../css/h/hh3_j8aeb.css';
import '../../css/r/rqsccpugz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qjeh93b6f"/><path class="hh3_j8aeb"/><path class="rqsccpugz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:archlinux-wordmark" {...props}></Icon>
