<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tatiy3bwz.css';
import '../../css/o/oqknzwbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tatiy3bwz"/><path class="oqknzwbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pricing-container" {...props}></Icon>
