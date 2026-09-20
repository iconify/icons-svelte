<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu0vtk99p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bu0vtk99p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bone-solid" {...props}></Icon>
