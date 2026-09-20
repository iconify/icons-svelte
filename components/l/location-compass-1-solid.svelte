<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcgmd2b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mcgmd2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-compass-1-solid" {...props}></Icon>
