<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv65oib5o.css';
import '../../css/n/n7ab-r98n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pv65oib5o"/><path class="n7ab-r98n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:qr-code" {...props}></Icon>
