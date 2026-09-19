<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbr_dz7cx.css';
import '../../css/q/q8pmglblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kbr_dz7cx"/><path class="q8pmglblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkmark-filled" {...props}></Icon>
