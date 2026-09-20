<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_nv4obkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_nv4obkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:first-order-alt" {...props}></Icon>
