<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6u0kfq8u.css';
import '../../css/m/mytk_qdsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6u0kfq8u"/><path class="mytk_qdsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mic" {...props}></Icon>
