<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkcugybwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jkcugybwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-2" {...props}></Icon>
