<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_dv-4xcr.css';
import '../../css/p/pk2ci7bwz.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d_dv-4xcr"/><path class="pk2ci7bwz"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-signed-20" {...props}></Icon>
