<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn3-n0bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pn3-n0bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:list-alt" {...props}></Icon>
