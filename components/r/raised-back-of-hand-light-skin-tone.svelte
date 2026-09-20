<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn-gz2b-c.css';
import '../../css/g/g8uv-0b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pn-gz2b-c"/><path class="g8uv-0b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:raised-back-of-hand-light-skin-tone" {...props}></Icon>
