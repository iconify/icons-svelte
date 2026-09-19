<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq0gx_bgt.css';
import '../../css/w/w6a568a7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fq0gx_bgt"/><path class="w6a568a7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-switch" {...props}></Icon>
