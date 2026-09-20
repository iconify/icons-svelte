<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud03tlhci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud03tlhci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-homepage-light" {...props}></Icon>
