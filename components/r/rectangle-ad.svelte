<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppq8x2-2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ppq8x2-2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rectangle-ad" {...props}></Icon>
