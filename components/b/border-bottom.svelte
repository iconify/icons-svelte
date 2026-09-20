<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw16btbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dw16btbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:border-bottom" {...props}></Icon>
