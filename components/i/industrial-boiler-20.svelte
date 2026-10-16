<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwuwdzb4d.css';
import '../../css/b/bxnfngy9v.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kwuwdzb4d"/><path class="bxnfngy9v"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:industrial-boiler-20" {...props}></Icon>
