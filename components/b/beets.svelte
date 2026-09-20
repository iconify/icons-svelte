<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx3nz_bus.css';
import '../../css/n/ndo424b7h.css';
import '../../css/q/q8jig3bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rx3nz_bus"/><path class="ndo424b7h"/><path class="q8jig3bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets" {...props}></Icon>
