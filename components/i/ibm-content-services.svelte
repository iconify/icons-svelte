<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rch7_ebcb.css';
import '../../css/r/r8xugpl5l.css';
import '../../css/t/taq167thd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rch7_ebcb"/><path class="r8xugpl5l"/><path class="taq167thd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-content-services" {...props}></Icon>
