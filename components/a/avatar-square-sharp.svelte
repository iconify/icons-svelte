<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z61j5nz5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z61j5nz5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:avatar-square-sharp" {...props}></Icon>
