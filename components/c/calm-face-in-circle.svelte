<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8xjub8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="es8xjub8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:calm-face-in-circle" {...props}></Icon>
