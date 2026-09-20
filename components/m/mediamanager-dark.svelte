<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw2ojp_cc.css';
import '../../css/e/e04op1bwe.css';
import '../../css/g/gutycobgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw2ojp_cc"/><path class="e04op1bwe"/><path class="gutycobgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamanager-dark" {...props}></Icon>
