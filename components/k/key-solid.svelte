<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccc5fnb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccc5fnb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:key-solid" {...props}></Icon>
