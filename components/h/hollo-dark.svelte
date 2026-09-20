<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf0zp_bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bf0zp_bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hollo-dark" {...props}></Icon>
