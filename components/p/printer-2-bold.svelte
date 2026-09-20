<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hm0g4b99a.css';
import '../../css/e/e12r68bme.css';
import '../../css/z/zhmxno9se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hm0g4b99a"/><path class="e12r68bme"/><path class="zhmxno9se"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-2-bold" {...props}></Icon>
