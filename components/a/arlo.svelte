<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl0xambhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sl0xambhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arlo" {...props}></Icon>
