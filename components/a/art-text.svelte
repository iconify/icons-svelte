<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtyo55uzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtyo55uzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:art-text" {...props}></Icon>
