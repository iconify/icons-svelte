<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3tfc2boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q3tfc2boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrows-vertical" {...props}></Icon>
