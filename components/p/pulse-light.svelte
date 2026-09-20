<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ota9e_b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ota9e_b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulse-light" {...props}></Icon>
