<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdicv_b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xdicv_b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-box-gabled-building-with-chimney" {...props}></Icon>
