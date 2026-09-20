<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzleqd5vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzleqd5vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-line" {...props}></Icon>
