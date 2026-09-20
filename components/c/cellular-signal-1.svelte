<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ztg_ejc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ztg_ejc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cellular-signal-1" {...props}></Icon>
