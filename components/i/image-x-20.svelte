<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3s1ebb3w.css';
import '../../css/p/puyefyg7s.css';
import '../../css/p/puz5jibvr.css';
import '../../css/e/ed4mxccbx.css';
import '../../css/e/eqdr87b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k3s1ebb3w"/><path class="puyefyg7s"/><path class="puz5jibvr"/><path class="ed4mxccbx"/><path class="eqdr87b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-x-20" {...props}></Icon>
