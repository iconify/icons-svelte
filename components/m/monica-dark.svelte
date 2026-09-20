<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hve1lylaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hve1lylaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monica-dark" {...props}></Icon>
