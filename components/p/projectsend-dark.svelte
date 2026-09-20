<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkv5ngb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkv5ngb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:projectsend-dark" {...props}></Icon>
