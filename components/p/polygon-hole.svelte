<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kttkocmdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kttkocmdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon-hole" {...props}></Icon>
