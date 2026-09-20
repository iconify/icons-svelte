<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftd6m5bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftd6m5bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:philips-hue-dark" {...props}></Icon>
