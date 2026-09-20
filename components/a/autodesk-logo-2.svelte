<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxh8guhzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxh8guhzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:autodesk-logo-2" {...props}></Icon>
