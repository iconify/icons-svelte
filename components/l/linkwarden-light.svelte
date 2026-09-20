<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsmnm9b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wsmnm9b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkwarden-light" {...props}></Icon>
