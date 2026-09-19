<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be94h47pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="be94h47pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:droplet-slash" {...props}></Icon>
