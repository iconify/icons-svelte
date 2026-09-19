<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_bcm4bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_bcm4bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hard-drive" {...props}></Icon>
