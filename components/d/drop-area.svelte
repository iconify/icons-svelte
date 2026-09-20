<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r06aysbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r06aysbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:drop-area" {...props}></Icon>
