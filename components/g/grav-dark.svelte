<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jom0v3bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jom0v3bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grav-dark" {...props}></Icon>
