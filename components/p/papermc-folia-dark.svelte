<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs-7npbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zs-7npbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-folia-dark" {...props}></Icon>
