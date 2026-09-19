<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0xrxiblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f0xrxiblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codeship" {...props}></Icon>
