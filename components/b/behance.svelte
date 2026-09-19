<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq82k-blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="uq82k-blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:behance" {...props}></Icon>
