<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b52jpbbmn.css';
import '../../css/q/q8xi7ko3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="b52jpbbmn"/><path class="q8xi7ko3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-scan-line" {...props}></Icon>
