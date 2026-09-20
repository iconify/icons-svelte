<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opw2n6p2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="opw2n6p2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cilium-light" {...props}></Icon>
