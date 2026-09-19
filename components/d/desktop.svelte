<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dupq9r-yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1664};
const content = `<path class="dupq9r-yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:desktop" {...props}></Icon>
