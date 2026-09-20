<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4dtb0bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4dtb0bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-off-line" {...props}></Icon>
