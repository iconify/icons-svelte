<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnizrebhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnizrebhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-justify-end" {...props}></Icon>
