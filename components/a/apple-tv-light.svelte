<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8-j1zyzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8-j1zyzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apple-tv-light" {...props}></Icon>
