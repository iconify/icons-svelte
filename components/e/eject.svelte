<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3utnwbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":480};
const content = `<path class="t3utnwbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:eject" {...props}></Icon>
