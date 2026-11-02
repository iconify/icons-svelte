<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyv7r-wuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyv7r-wuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dna-line" {...props}></Icon>
