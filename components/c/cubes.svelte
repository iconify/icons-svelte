<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj70f5b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gj70f5b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cubes" {...props}></Icon>
