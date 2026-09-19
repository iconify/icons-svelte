<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev1fg5bdw.css';
import '../../css/j/j8_u0x2hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ev1fg5bdw"/><path class="j8_u0x2hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:crop-outline" {...props}></Icon>
