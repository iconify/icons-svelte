<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9hpp2nbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l9hpp2nbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-on-pickup-truck" {...props}></Icon>
