<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucpq15tnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ucpq15tnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-expand-sharp" {...props}></Icon>
