<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp440nu6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp440nu6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medassist-light" {...props}></Icon>
