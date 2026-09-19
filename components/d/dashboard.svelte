<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd8_36abv.css';
import '../../css/d/de8636buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vd8_36abv"/><path class="de8636buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dashboard" {...props}></Icon>
