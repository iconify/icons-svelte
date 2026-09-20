<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi5-9xmbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fi5-9xmbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:map-location-solid" {...props}></Icon>
