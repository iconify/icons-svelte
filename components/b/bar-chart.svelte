<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkwho5o2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nkwho5o2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bar-chart" {...props}></Icon>
