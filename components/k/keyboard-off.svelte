<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joxwt1bet.css';
import '../../css/k/kdd-004ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="joxwt1bet"/><path class="kdd-004ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:keyboard-off" {...props}></Icon>
