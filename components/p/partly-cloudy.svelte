<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo3l2xb1x.css';
import '../../css/m/mdqwd7bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uo3l2xb1x"/><path class="mdqwd7bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:partly-cloudy" {...props}></Icon>
