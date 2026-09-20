<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpm9sb8kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mpm9sb8kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ellipsis" {...props}></Icon>
