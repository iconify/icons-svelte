<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9wgdtbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9wgdtbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:map-pin" {...props}></Icon>
