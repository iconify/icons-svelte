<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flx-ib50r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="flx-ib50r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:heat-map-chart-filled" {...props}></Icon>
