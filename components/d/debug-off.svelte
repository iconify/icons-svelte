<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci8rwmejd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8rwmejd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:debug-off" {...props}></Icon>
