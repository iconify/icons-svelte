<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6tmrrbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f6tmrrbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:disc-golf-basket" {...props}></Icon>
