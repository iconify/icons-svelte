<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_nc4u1cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j_nc4u1cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pyramid-shape-solid" {...props}></Icon>
