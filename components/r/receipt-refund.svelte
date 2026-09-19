<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myl2x9bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="myl2x9bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:receipt-refund" {...props}></Icon>
