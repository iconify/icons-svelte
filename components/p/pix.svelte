<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggdnmsb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggdnmsb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:pix" {...props}></Icon>
