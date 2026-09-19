<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krm_rrbhp.css';
import '../../css/q/q1h9w_bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krm_rrbhp"/><path class="q1h9w_bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:exposure" {...props}></Icon>
