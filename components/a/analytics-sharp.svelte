<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg5eemufk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5eemufk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:analytics-sharp" {...props}></Icon>
