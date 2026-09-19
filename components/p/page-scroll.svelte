<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp_ojgx_e.css';
import '../../css/q/q-roxqdob.css';
import '../../css/o/oc7q7_bck.css';
import '../../css/k/kgeui_bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rp_ojgx_e"/><path class="q-roxqdob"/><path class="oc7q7_bck"/><path class="kgeui_bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:page-scroll" {...props}></Icon>
