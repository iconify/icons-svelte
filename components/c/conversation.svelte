<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub10_dwjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ub10_dwjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:conversation" {...props}></Icon>
