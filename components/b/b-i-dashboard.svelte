<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy7m0b3bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uy7m0b3bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:b-i-dashboard" {...props}></Icon>
