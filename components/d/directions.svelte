<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7c02-ygu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="x7c02-ygu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:directions" {...props}></Icon>
