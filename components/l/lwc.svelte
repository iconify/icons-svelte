<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2wg_xbzr.css';
import '../../css/h/huflwkbsf.css';
import '../../css/y/yp4zj8ohv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x2wg_xbzr"/><path class="huflwkbsf"/><path class="yp4zj8ohv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:lwc" {...props}></Icon>
