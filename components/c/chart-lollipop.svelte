<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh_k5d__w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uh_k5d__w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-lollipop" {...props}></Icon>
