<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pug4ir7hv.css';
import '../../css/c/crznqgb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="pug4ir7hv"/><path class="crznqgb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:enter-down" {...props}></Icon>
