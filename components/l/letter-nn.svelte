<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asfl_abgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="asfl_abgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-nn" {...props}></Icon>
