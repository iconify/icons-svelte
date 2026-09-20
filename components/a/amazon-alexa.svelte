<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzw45xbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzw45xbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-alexa" {...props}></Icon>
