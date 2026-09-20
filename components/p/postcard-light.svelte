<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_pewl6-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_pewl6-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postcard-light" {...props}></Icon>
