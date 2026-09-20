<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr9qn8b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rr9qn8b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare-dark" {...props}></Icon>
