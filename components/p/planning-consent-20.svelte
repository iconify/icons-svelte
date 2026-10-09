<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_dv-4xcr.css';
import '../../css/x/xb74i3b_v.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d_dv-4xcr"/><path class="xb74i3b_v"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:planning-consent-20" {...props}></Icon>
