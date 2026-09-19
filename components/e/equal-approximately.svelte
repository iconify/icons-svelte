<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l15f58bue.css';
import '../../css/m/mxv0-rl9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l15f58bue"/><path class="mxv0-rl9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:equal-approximately" {...props}></Icon>
