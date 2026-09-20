<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djbz6iboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djbz6iboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-worm-dark" {...props}></Icon>
