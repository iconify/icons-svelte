<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipp9v_bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipp9v_bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-lock-1" {...props}></Icon>
