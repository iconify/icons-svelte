<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-uq9dcxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-uq9dcxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:robot-sharp" {...props}></Icon>
