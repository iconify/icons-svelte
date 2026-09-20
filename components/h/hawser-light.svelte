<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpju4jbvx.css';
import '../../css/t/tqpmf_bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tpju4jbvx"/><path class="tqpmf_bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser-light" {...props}></Icon>
