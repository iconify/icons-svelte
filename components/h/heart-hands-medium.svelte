<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pny3j9blh.css';
import '../../css/q/qczzyabmn.css';
import '../../css/i/i4kg29big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pny3j9blh"/><path clip-rule="evenodd" class="qczzyabmn"/><path class="i4kg29big"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:heart-hands-medium" {...props}></Icon>
