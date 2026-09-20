<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_z3mvb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_z3mvb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pyload-dark" {...props}></Icon>
