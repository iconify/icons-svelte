<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le-2l4b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="le-2l4b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-area-stepper" {...props}></Icon>
