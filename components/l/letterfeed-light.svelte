<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp6fcs6dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zp6fcs6dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:letterfeed-light" {...props}></Icon>
