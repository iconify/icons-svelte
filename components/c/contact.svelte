<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3iw_nbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3iw_nbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:contact" {...props}></Icon>
