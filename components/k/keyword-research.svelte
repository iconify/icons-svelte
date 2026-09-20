<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5z5kabyv.css';
import '../../css/k/kd452xpng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o5z5kabyv"/><path class="kd452xpng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:keyword-research" {...props}></Icon>
