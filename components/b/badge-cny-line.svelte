<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggxo8pl6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggxo8pl6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-cny-line" {...props}></Icon>
