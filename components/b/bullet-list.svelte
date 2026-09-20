<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4ti73b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r4ti73b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bullet-list" {...props}></Icon>
