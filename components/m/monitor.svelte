<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xywejhb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xywejhb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:monitor" {...props}></Icon>
