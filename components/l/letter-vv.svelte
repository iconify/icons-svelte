<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksq4q7bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ksq4q7bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-vv" {...props}></Icon>
