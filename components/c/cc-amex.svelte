<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l05o_pbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l05o_pbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-amex" {...props}></Icon>
