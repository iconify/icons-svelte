<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_k6153t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7_k6153t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-color" {...props}></Icon>
