<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4gm1rbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4gm1rbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-ruble" {...props}></Icon>
