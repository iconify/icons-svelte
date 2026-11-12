<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5rb22bzv.css';
import '../../css/a/ad4ln5bah.css';
import '../../css/y/y0wutcc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p5rb22bzv"/><path class="ad4ln5bah"/><path class="y0wutcc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dawarich-dark" {...props}></Icon>
