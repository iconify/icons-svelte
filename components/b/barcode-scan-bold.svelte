<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-gxh01qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-gxh01qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:barcode-scan-bold" {...props}></Icon>
