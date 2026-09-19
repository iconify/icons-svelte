<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2slab6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ml2slab6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:pointer" {...props}></Icon>
