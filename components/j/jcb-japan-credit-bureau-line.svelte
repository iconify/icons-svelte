<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1z4bsb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1z4bsb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jcb-japan-credit-bureau-line" {...props}></Icon>
