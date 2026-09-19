<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me1not0hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="cls-1 me1not0hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:pied-piper" {...props}></Icon>
