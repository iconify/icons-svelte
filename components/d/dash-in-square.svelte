<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd0-3i1_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bd0-3i1_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:dash-in-square" {...props}></Icon>
