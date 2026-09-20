<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2mx2ubfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2mx2ubfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbpad-dark" {...props}></Icon>
