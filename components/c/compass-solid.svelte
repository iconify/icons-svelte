<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stku8xd3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stku8xd3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:compass-solid" {...props}></Icon>
