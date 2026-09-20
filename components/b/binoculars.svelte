<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku_b133lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ku_b133lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:binoculars" {...props}></Icon>
