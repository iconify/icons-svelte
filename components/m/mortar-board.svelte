<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq-ba649u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zq-ba649u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mortar-board" {...props}></Icon>
