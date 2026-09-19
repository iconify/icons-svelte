<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0gxjcbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0gxjcbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flame" {...props}></Icon>
