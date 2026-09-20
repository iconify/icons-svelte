<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq0eo_b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq0eo_b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-c-circle" {...props}></Icon>
