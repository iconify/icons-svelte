<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4spp6b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4spp6b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:geocaching" {...props}></Icon>
