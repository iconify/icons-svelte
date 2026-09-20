<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtpfbmb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dtpfbmb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:deer-head-under-paragraph" {...props}></Icon>
