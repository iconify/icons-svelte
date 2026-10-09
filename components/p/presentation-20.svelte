<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pze-k_dmv.css';
import '../../css/a/ad5vgcley.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pze-k_dmv"/><path class="ad5vgcley"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:presentation-20" {...props}></Icon>
