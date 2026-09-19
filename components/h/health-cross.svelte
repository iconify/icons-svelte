<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1o7hk86y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i1o7hk86y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:health-cross" {...props}></Icon>
