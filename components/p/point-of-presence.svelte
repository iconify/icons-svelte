<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cztp4ub5c.css';
import '../../css/x/xn7w50bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cztp4ub5c"/><path class="xn7w50bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:point-of-presence" {...props}></Icon>
