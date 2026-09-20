<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhlhglulc.css';
import '../../css/k/k1nvv5m4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":240};
const content = `<path class="fhlhglulc"/><path class="k1nvv5m4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:affinity" {...props}></Icon>
