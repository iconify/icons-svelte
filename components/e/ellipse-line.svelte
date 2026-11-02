<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gctyc2rag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gctyc2rag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ellipse-line" {...props}></Icon>
