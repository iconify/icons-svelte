<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqxmbub4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wqxmbub4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:receipt-check-solid" {...props}></Icon>
