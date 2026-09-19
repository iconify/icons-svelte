<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4k767w9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="y4k767w9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:rev" {...props}></Icon>
