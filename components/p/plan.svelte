<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smumombga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="smumombga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:plan" {...props}></Icon>
