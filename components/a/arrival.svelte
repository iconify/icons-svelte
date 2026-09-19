<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj2r8npqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kj2r8npqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrival" {...props}></Icon>
