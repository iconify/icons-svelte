<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_vvn0brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_vvn0brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:barcode" {...props}></Icon>
