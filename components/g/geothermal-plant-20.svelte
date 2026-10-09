<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppj2e6b_r.css';
import '../../css/p/p5xgy2blo.css';
import '../../css/b/b7vjddz7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ppj2e6b_r"/><path class="p5xgy2blo"/><path class="b7vjddz7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-20" {...props}></Icon>
