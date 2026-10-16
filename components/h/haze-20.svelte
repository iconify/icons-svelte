<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_hv1kb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_hv1kb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:haze-20" {...props}></Icon>
