<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayvdx43dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayvdx43dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:equipment-outline" {...props}></Icon>
