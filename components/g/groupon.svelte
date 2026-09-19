<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/simr-3b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="simr-3b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:groupon" {...props}></Icon>
