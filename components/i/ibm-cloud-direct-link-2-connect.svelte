<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv5vedcrf.css';
import '../../css/h/hao8iibvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kv5vedcrf"/><path class="hao8iibvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-direct-link-2-connect" {...props}></Icon>
