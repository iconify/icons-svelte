<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0u-v_b0l.css';
import '../../css/o/oouf8iqje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0u-v_b0l"/><path class="oouf8iqje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare-zero-trust-light" {...props}></Icon>
