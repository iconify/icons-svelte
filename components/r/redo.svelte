<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2j7_lbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2j7_lbyc st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:redo" {...props}></Icon>
