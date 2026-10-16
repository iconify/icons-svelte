<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei8_htdz.css';
import '../../css/s/s-d9er3vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="s-d9er3vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydro-20-bold" {...props}></Icon>
