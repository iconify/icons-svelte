<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8r095um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="es8r095um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:redo" {...props}></Icon>
