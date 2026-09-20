<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7wmwym2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m7wmwym2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-down-2" {...props}></Icon>
