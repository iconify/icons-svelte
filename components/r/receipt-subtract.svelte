<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cac-zsbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cac-zsbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:receipt-subtract" {...props}></Icon>
