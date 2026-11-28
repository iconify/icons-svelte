<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjhwy-bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rjhwy-bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:replay-10-thin" {...props}></Icon>
