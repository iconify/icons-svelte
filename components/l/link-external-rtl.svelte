<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djym6wg5f.css';
import '../../css/v/vdsmzq_1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="djym6wg5f"/><path class="vdsmzq_1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:link-external-rtl" {...props}></Icon>
