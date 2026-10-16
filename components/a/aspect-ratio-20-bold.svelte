<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-w1mof7v.css';
import '../../css/l/lzskzeb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b-w1mof7v"/><path class="lzskzeb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aspect-ratio-20-bold" {...props}></Icon>
