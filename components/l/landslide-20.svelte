<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abw1tpbib.css';
import '../../css/f/fsolhac6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abw1tpbib"/><path class="fsolhac6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landslide-20" {...props}></Icon>
