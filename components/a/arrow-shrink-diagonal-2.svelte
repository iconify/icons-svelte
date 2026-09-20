<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4auf4bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r4auf4bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-shrink-diagonal-2" {...props}></Icon>
