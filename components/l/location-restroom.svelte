<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1pfkf74d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1pfkf74d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:location-restroom" {...props}></Icon>
