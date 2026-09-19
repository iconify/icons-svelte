<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zryp4sb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zryp4sb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-circle-xmark" {...props}></Icon>
