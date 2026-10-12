<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la_t-mbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="la_t-mbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-stroke-20" {...props}></Icon>
