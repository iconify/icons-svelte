<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0usfcc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0usfcc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:barcode-1" {...props}></Icon>
