<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/ohlpaj_qx.css';
import '../../css/i/i6lvci1zi.css';
import '../../css/e/ejq2wacjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="ohlpaj_qx"/><path class="i6lvci1zi"/></g><circle class="ejq2wacjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-error-stroke-12" {...props}></Icon>
