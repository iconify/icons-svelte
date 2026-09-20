<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc5obibsk.css';
import '../../css/f/fg1jarbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yc5obibsk"/><path class="fg1jarbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-web-services" {...props}></Icon>
