<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo7lrcqop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="uo7lrcqop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mask-face" {...props}></Icon>
