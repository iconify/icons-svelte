<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-f5cn18w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-f5cn18w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:funkwhale-dark" {...props}></Icon>
