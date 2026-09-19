<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxzr4tbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxzr4tbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lemon" {...props}></Icon>
