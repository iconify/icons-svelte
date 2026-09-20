<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xzntu9doz.css';
import '../../css/e/e12r68bme.css';
import '../../css/g/gn31iacux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xzntu9doz"/><path class="e12r68bme"/><path clip-rule="evenodd" class="gn31iacux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-bold" {...props}></Icon>
