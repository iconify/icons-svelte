<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juorm-blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juorm-blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fault-line" {...props}></Icon>
