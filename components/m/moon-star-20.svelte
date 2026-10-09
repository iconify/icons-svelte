<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpdrb_b_d.css';
import '../../css/v/vqx3s2bml.css';
import '../../css/j/jmxwfobcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qpdrb_b_d"/><path class="vqx3s2bml"/><path class="jmxwfobcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-star-20" {...props}></Icon>
