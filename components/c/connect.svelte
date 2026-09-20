<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ej5itcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9ej5itcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:connect" {...props}></Icon>
