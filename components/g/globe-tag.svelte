<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eio5m-zyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eio5m-zyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:globe-tag" {...props}></Icon>
