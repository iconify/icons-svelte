<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq10agx6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qq10agx6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cut" {...props}></Icon>
