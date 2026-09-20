<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdhcrkb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdhcrkb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextbeats-light" {...props}></Icon>
