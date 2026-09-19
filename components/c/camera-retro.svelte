<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdfa1mbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="hdfa1mbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:camera-retro" {...props}></Icon>
