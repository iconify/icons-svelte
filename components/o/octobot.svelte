<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdph_mk2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdph_mk2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octobot" {...props}></Icon>
