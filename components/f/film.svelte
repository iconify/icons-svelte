<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuxx9b2_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kuxx9b2_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:film" {...props}></Icon>
