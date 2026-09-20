<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc_q4r-ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_q4r-ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flowerpot-line" {...props}></Icon>
