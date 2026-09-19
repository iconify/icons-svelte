<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwnuoacob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qwnuoacob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ieee-square" {...props}></Icon>
