<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lerkp7hns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lerkp7hns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:power-off" {...props}></Icon>
