<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmb9pi-5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dmb9pi-5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:files" {...props}></Icon>
