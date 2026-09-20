<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg089kb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tg089kb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulsarr-dark" {...props}></Icon>
