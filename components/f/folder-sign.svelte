<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp0p0ibwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gp0p0ibwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:folder-sign" {...props}></Icon>
