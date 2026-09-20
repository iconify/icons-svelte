<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpg_34pwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpg_34pwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myip-light" {...props}></Icon>
