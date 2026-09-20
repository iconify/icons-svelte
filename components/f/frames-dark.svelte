<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie_d5yb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie_d5yb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frames-dark" {...props}></Icon>
