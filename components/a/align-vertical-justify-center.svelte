<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9n8h903w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9n8h903w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-justify-center" {...props}></Icon>
