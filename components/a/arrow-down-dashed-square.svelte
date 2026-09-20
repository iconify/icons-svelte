<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unsftc1qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="unsftc1qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-down-dashed-square" {...props}></Icon>
