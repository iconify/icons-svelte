<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc2qde7lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2qde7lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-medium" {...props}></Icon>
