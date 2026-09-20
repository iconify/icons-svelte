<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl-6ywx-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl-6ywx-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:refresh" {...props}></Icon>
