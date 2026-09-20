<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj0d_qbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qj0d_qbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-search-check" {...props}></Icon>
