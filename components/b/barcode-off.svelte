<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk3k_6m-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3k_6m-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:barcode-off" {...props}></Icon>
