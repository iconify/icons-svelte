<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu6la5bgc.css';
import '../../css/f/fhhuixbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tu6la5bgc"/><path class="fhhuixbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exit-fill-16" {...props}></Icon>
