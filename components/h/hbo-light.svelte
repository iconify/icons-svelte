<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-_htb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sz-_htb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hbo-light" {...props}></Icon>
