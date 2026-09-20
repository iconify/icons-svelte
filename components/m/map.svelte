<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb4xkrb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb4xkrb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:map" {...props}></Icon>
