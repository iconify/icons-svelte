<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8t2-ybfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8t2-ybfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homarr" {...props}></Icon>
