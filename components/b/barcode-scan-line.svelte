<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d90rggb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d90rggb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-scan-line" {...props}></Icon>
