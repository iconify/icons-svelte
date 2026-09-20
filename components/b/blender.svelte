<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1wmfxbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1wmfxbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blender" {...props}></Icon>
