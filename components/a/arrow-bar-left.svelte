<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7junnlin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7junnlin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-bar-left" {...props}></Icon>
