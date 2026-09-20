<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mloygh_vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mloygh_vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-plus" {...props}></Icon>
