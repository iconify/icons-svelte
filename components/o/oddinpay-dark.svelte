<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loraotb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":35};
const content = `<path class="loraotb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oddinpay-dark" {...props}></Icon>
