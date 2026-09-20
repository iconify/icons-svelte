<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv9r3v_hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yv9r3v_hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:discloud" {...props}></Icon>
