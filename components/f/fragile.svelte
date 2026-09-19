<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpcetyksa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kpcetyksa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fragile" {...props}></Icon>
