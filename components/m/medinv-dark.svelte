<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv5t23ldk.css';
import '../../css/o/oqpqr4qja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv5t23ldk"/><circle class="oqpqr4qja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medinv-dark" {...props}></Icon>
