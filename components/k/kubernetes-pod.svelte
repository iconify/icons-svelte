<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsrzeq-ig.css';
import '../../css/u/um_le5b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hsrzeq-ig"/><path class="um_le5b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kubernetes-pod" {...props}></Icon>
