<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rktkv5b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rktkv5b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:follow-up-work-order" {...props}></Icon>
