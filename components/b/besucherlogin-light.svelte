<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq7-tmb6k.css';
import '../../css/t/tofm4bbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq7-tmb6k"/><rect class="tofm4bbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:besucherlogin-light" {...props}></Icon>
