<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n58zy-blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n58zy-blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hospital-symbol" {...props}></Icon>
