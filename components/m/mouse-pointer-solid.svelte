<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff1u0l6vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ff1u0l6vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mouse-pointer-solid" {...props}></Icon>
