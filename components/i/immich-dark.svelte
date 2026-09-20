<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfn34bccd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfn34bccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-dark" {...props}></Icon>
