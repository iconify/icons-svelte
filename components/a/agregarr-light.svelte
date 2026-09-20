<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6f5zlbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6f5zlbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agregarr-light" {...props}></Icon>
