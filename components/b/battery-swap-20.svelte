<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lma-9b7ei.css';
import '../../css/k/ki6vv-b4z.css';
import '../../css/o/om_n_ebsy.css';
import '../../css/f/f_ct1n54q.css';
import '../../css/j/jt0uzybsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lma-9b7ei"/><path class="ki6vv-b4z"/><path class="om_n_ebsy"/><path class="f_ct1n54q"/><path class="jt0uzybsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-swap-20" {...props}></Icon>
