<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy4g9dohn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy4g9dohn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papra-light" {...props}></Icon>
