<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqn-v9b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="iqn-v9b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:receipt" {...props}></Icon>
