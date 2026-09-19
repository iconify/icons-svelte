<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0jalubpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r0jalubpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-redo-stroke-12" {...props}></Icon>
