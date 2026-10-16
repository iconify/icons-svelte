<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bizml48vp.css';
import '../../css/r/r-vw3obhe.css';
import '../../css/r/rk9-55a5q.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bizml48vp"/><path class="r-vw3obhe"/><path class="rk9-55a5q"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parliament-20" {...props}></Icon>
