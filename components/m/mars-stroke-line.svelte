<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/latfltb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="latfltb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mars-stroke-line" {...props}></Icon>
