<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0h1vccah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k0h1vccah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-bar-stacked" {...props}></Icon>
