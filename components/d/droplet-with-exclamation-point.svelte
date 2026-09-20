<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcl98g9-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mcl98g9-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-with-exclamation-point" {...props}></Icon>
