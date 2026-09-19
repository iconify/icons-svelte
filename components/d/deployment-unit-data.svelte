<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs5lclkzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cs5lclkzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-unit-data" {...props}></Icon>
