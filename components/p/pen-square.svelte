<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx40f8buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx40f8buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:pen-square" {...props}></Icon>
