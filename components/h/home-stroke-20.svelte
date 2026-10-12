<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9kr3ubxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9kr3ubxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-stroke-20" {...props}></Icon>
