<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdps-gl2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdps-gl2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:roblox-studio" {...props}></Icon>
