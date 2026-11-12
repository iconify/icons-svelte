<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueisbo96q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ueisbo96q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:i-librarian-light" {...props}></Icon>
