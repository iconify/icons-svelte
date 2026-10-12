<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-w8eybpe.css';
import '../../css/o/oi7kg_bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e-w8eybpe"/><path class="oi7kg_bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bear-48-bold" {...props}></Icon>
