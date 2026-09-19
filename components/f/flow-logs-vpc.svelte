<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv63tfbxq.css';
import '../../css/f/fi_q4_r5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bv63tfbxq"/><path class="fi_q4_r5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-logs-vpc" {...props}></Icon>
