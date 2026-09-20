<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8qw16bmp.css';
import '../../css/r/rqcx1bj2b.css';
import '../../css/u/udfii55xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8qw16bmp"/><path class="rqcx1bj2b"/><path class="udfii55xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:catheon" {...props}></Icon>
