<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqreai28o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272,"height":432};
const content = `<path class="kqreai28o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-old" {...props}></Icon>
