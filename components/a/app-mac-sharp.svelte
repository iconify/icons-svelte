<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t58hyebaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t58hyebaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:app-mac-sharp" {...props}></Icon>
