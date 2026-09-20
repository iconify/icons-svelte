<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqvwqo0sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqvwqo0sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hetrixtools-light" {...props}></Icon>
