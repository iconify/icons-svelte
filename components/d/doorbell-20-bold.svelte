<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj44hh7wm.css';
import '../../css/g/gap1gyb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wj44hh7wm"/><path class="gap1gyb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:doorbell-20-bold" {...props}></Icon>
