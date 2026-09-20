<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhxz97bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxz97bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-x-sharp" {...props}></Icon>
