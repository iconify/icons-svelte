<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_l4hqb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_l4hqb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:barcode-search" {...props}></Icon>
