<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idkbi6nqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="idkbi6nqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-50-percent" {...props}></Icon>
