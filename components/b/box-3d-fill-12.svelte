<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlvssrboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zlvssrboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-3d-fill-12" {...props}></Icon>
