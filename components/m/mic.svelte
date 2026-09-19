<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v95ogbcrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":408};
const content = `<path class="v95ogbcrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mic" {...props}></Icon>
