<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc9zr_r5s.css';
import '../../css/d/d3xjujk0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nc9zr_r5s"/><path class="d3xjujk0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:libgdx" {...props}></Icon>
