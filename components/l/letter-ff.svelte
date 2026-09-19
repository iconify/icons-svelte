<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6v0xg95w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l6v0xg95w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-ff" {...props}></Icon>
