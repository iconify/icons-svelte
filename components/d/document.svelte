<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0odedbyc.css';
import '../../css/f/ffal_wb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y0odedbyc"/><path class="ffal_wb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document" {...props}></Icon>
