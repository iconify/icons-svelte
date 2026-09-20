<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-4mcrbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-4mcrbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-justify-center-sharp" {...props}></Icon>
