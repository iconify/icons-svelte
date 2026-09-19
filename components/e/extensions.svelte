<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs1mqdbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gs1mqdbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:extensions" {...props}></Icon>
