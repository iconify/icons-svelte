<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ans_9vb2b.css';
import '../../css/x/xsyo_cc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ans_9vb2b"/><path class="xsyo_cc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-left-20-bold" {...props}></Icon>
