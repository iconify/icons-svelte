<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcebbxirw.css';
import '../../css/m/m374-eb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tcebbxirw"/><path class="m374-eb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paypal-original" {...props}></Icon>
