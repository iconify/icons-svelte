<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mssa0nb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="mssa0nb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:globe-alt" {...props}></Icon>
