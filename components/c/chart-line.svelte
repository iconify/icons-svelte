<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgvk7ab5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgvk7ab5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chart-line" {...props}></Icon>
