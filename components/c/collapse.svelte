<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9mowj1_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9mowj1_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:collapse" {...props}></Icon>
