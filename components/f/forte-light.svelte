<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wak_5j_yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wak_5j_yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forte-light" {...props}></Icon>
