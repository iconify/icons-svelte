<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmogvib1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hmogvib1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:eraser-solid" {...props}></Icon>
