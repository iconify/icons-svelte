<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0n8kv_ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0n8kv_ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-check-ok" {...props}></Icon>
