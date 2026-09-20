<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5vj-ib1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5vj-ib1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orca-slicer-light" {...props}></Icon>
