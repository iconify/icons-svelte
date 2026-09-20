<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnnd0yb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dnnd0yb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:butcher-14" {...props}></Icon>
