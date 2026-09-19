<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo8f6ub5d.css';
import '../../css/i/ibm4w8blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8f6ub5d"/><path class="ibm4w8blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bomb" {...props}></Icon>
