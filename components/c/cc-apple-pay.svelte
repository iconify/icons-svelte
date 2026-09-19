<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5dc-7bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s5dc-7bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-apple-pay" {...props}></Icon>
