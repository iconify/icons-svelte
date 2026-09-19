<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rovpu9_sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rovpu9_sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:minus-plus" {...props}></Icon>
