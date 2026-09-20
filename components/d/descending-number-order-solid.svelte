<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt97lnugv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tt97lnugv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:descending-number-order-solid" {...props}></Icon>
