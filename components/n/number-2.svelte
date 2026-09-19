<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkaabgb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rkaabgb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-2" {...props}></Icon>
