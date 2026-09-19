<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhp76k4yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rhp76k4yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mapping-show" {...props}></Icon>
