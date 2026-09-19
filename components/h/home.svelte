<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8zx3bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k_8zx3bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:home" {...props}></Icon>
