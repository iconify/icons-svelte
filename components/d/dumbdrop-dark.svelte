<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0h-p-b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0h-p-b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdrop-dark" {...props}></Icon>
