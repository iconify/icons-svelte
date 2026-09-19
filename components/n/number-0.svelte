<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0bxq3day.css';
import '../../css/e/e3t8n_b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0bxq3day"/><path class="e3t8n_b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-0" {...props}></Icon>
