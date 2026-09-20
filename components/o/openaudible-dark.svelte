<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk4ea3bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yk4ea3bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openaudible-dark" {...props}></Icon>
