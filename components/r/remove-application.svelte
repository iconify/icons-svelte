<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vthoncfqk.css';
import '../../css/m/mlv6tlbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="vthoncfqk"/><path class="mlv6tlbcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remove-application" {...props}></Icon>
