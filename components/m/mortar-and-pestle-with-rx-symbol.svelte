<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqaqnlb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sqaqnlb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mortar-and-pestle-with-rx-symbol" {...props}></Icon>
