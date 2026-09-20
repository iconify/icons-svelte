<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfhf6tbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfhf6tbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atria-light" {...props}></Icon>
