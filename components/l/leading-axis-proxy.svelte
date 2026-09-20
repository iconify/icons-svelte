<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv6_a4bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pv6_a4bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:leading-axis-proxy" {...props}></Icon>
