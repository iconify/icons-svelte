<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbr_1wbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbr_1wbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:qr-code-x" {...props}></Icon>
