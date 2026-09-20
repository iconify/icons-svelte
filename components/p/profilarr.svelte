<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ec5ibda.css';
import '../../css/z/z82ckhzmf.css';
import '../../css/j/jf_8h71yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6ec5ibda"/><path class="z82ckhzmf"/><path class="jf_8h71yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:profilarr" {...props}></Icon>
