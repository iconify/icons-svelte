<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ans_9vb2b.css';
import '../../css/a/az1dy05bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ans_9vb2b"/><path class="az1dy05bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:close-20-bold" {...props}></Icon>
