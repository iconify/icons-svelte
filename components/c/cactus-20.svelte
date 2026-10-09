<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnes2-b0p.css';
import '../../css/w/wofyv04is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hnes2-b0p"/><path class="wofyv04is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cactus-20" {...props}></Icon>
