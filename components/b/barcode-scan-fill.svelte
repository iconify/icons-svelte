<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b52jpbbmn.css';
import '../../css/m/mtymvigmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b52jpbbmn"/><path class="mtymvigmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-scan-fill" {...props}></Icon>
