<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmq_8zrle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmq_8zrle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-intelligence-frame-line" {...props}></Icon>
