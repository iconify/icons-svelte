<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n12kwabfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n12kwabfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:cart" {...props}></Icon>
