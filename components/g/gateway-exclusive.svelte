<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm02tab2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wm02tab2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gateway-exclusive" {...props}></Icon>
