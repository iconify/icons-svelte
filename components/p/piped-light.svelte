<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p75du9kle.css';
import '../../css/f/f08bsp95i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p75du9kle"/><path class="f08bsp95i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piped-light" {...props}></Icon>
