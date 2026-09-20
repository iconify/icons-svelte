<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq-k4bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvq-k4bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudinary" {...props}></Icon>
