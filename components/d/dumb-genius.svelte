<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opo08-b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="opo08-b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumb-genius" {...props}></Icon>
