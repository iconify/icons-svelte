<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfyvin1tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfyvin1tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-plus-fill-round" {...props}></Icon>
