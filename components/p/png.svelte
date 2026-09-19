<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c44cj2bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c44cj2bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:png" {...props}></Icon>
