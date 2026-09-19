<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgq_h0dcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pgq_h0dcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pen-square" {...props}></Icon>
