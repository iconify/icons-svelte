<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foflm7r3e.css';
import '../../css/t/tsj3hfbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="foflm7r3e"/><path class="tsj3hfbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coinmarketcap-blue" {...props}></Icon>
