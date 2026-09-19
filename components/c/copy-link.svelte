<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0_aafh7s.css';
import '../../css/o/oasg37s7n.css';
import '../../css/k/kfsga1-1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h0_aafh7s"/><path class="oasg37s7n"/><path class="kfsga1-1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:copy-link" {...props}></Icon>
