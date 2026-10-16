<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2hmebrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lh2hmebrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-mix-20" {...props}></Icon>
