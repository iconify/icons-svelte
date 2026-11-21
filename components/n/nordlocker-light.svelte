<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyvy9zbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyvy9zbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nordlocker-light" {...props}></Icon>
