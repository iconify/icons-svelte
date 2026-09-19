<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt0xhaboe.css';
import '../../css/i/ibygdfo4w.css';
import '../../css/x/xc__svjwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt0xhaboe"/><path class="ibygdfo4w"/><path class="xc__svjwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pushpin" {...props}></Icon>
