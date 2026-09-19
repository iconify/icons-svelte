<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1uwanbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p1uwanbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-3d-stroke-12" {...props}></Icon>
