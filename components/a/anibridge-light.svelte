<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swdvhieyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swdvhieyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anibridge-light" {...props}></Icon>
