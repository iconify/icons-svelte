<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkdf8eh1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hkdf8eh1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:restaurant-14" {...props}></Icon>
