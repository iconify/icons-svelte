<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t21kzacmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t21kzacmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:qrcode-line" {...props}></Icon>
