<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jof2l9d2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jof2l9d2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:r" {...props}></Icon>
