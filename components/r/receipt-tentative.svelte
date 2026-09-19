<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swq5i0brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="swq5i0brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:receipt-tentative" {...props}></Icon>
