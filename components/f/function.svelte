<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2jnib0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ma2jnib0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:function" {...props}></Icon>
