<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-5zy7bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-5zy7bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:comfyui" {...props}></Icon>
