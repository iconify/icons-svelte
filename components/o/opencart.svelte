<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9h6a3mpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="z9h6a3mpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:opencart" {...props}></Icon>
