<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0-mlhn1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o0-mlhn1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btc" {...props}></Icon>
