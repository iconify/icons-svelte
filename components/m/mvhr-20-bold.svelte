<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gro8lebrz.css';
import '../../css/c/c6_bjubqo.css';
import '../../css/d/d50-4zb9n.css';
import '../../css/r/rkepvhbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gro8lebrz"/><path class="c6_bjubqo"/><path class="d50-4zb9n"/><path class="rkepvhbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mvhr-20-bold" {...props}></Icon>
