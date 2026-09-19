<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_n2pacdg.css';
import '../../css/x/xsa49xbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_n2pacdg"/><path class="xsa49xbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:building" {...props}></Icon>
