<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlojlbxyx.css';
import '../../css/w/wvbfodbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlojlbxyx"/><path class="wvbfodbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:popup" {...props}></Icon>
