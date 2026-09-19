<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l-xq-1bpb.css';
import '../../css/e/e4n8cdcst.css';
import '../../css/k/k-vg18sac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l-xq-1bpb"/><path class="e4n8cdcst"/><path class="k-vg18sac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:clipboard" {...props}></Icon>
