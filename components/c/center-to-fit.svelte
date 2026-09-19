<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy8g74bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gy8g74bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:center-to-fit" {...props}></Icon>
