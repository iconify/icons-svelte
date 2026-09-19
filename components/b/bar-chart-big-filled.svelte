<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1ohtunpb.css';
import '../../css/u/uxtfceu2g.css';
import '../../css/q/qcfr4vtpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ohtunpb"/><rect class="uxtfceu2g"/><path class="qcfr4vtpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bar-chart-big-filled" {...props}></Icon>
