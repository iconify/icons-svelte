<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvzi22bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvzi22bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-inner" {...props}></Icon>
