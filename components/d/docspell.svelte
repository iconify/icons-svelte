<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keo_ub1ao.css';
import '../../css/m/mrxynabnu.css';
import '../../css/v/vgjcg77tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="keo_ub1ao"/><path class="mrxynabnu"/><path class="vgjcg77tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docspell" {...props}></Icon>
