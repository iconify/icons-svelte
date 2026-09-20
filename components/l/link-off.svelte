<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdiqizb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdiqizb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:link-off" {...props}></Icon>
