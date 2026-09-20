<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxhld3hlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhld3hlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-downasaur" {...props}></Icon>
