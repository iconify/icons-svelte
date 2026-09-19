<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwdjy4r4g.css';
import '../../css/c/cgsvaq7sr.css';
import '../../css/a/amuvk0bpt.css';
import '../../css/p/pavit-bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lwdjy4r4g"/><path class="cgsvaq7sr"/><path class="amuvk0bpt"/><path class="pavit-bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:puppeteer" {...props}></Icon>
