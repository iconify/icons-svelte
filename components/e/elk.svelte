<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg48uhzxf.css';
import '../../css/i/i-gh0uunf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg48uhzxf"/><path class="i-gh0uunf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elk" {...props}></Icon>
