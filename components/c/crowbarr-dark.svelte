<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqqafpd3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wqqafpd3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowbarr-dark" {...props}></Icon>
