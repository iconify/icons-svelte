<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flpk8vi4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flpk8vi4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:round-arrow-5" {...props}></Icon>
