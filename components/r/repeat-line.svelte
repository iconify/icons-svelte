<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuoxx-7fa.css';
import '../../css/q/qdqr_q1-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuoxx-7fa"/><path class="qdqr_q1-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:repeat-line" {...props}></Icon>
