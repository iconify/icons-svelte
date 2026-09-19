<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksc4jgbab.css';
import '../../css/w/wgsmb37wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ksc4jgbab"/><path class="wgsmb37wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-lpa" {...props}></Icon>
