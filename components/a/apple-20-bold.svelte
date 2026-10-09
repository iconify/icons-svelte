<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg0icab7b.css';
import '../../css/y/ybggmtbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qg0icab7b"/><path class="ybggmtbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apple-20-bold" {...props}></Icon>
