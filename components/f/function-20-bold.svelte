<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx4xreset.css';
import '../../css/h/hyx6j7bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qx4xreset"/><path class="hyx6j7bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:function-20-bold" {...props}></Icon>
