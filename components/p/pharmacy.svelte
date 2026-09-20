<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5yc1ib6b.css';
import '../../css/h/huno55bpx.css';
import '../../css/c/cuxq-5b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="j5yc1ib6b"/><path class="huno55bpx"/><path class="cuxq-5b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:pharmacy" {...props}></Icon>
