<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgdhurbaf.css';
import '../../css/n/nj8wk4a5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgdhurbaf"/><path class="nj8wk4a5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-firefly" {...props}></Icon>
