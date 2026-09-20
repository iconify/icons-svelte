<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcyq56q4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcyq56q4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:device-watch" {...props}></Icon>
