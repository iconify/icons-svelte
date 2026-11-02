<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltb8g75pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltb8g75pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-2-line" {...props}></Icon>
