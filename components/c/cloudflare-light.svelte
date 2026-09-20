<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef4c8rz-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ef4c8rz-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare-light" {...props}></Icon>
