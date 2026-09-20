<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kywogzbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kywogzbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-baby-changing-table" {...props}></Icon>
