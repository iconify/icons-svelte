<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dan00jbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dan00jbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-histogram" {...props}></Icon>
