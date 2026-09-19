<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbopcgp3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbopcgp3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-integration-server" {...props}></Icon>
