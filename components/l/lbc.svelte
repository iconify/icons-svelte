<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do_g2d87h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="do_g2d87h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lbc" {...props}></Icon>
