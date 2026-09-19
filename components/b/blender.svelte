<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzmb8kc6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="gzmb8kc6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:blender" {...props}></Icon>
