<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gue8-4pzr.css';
import '../../css/f/f1ijkjbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gue8-4pzr"/><path class="f1ijkjbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-custom" {...props}></Icon>
