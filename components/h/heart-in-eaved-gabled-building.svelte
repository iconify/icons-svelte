<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zers9_rqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zers9_rqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-in-eaved-gabled-building" {...props}></Icon>
