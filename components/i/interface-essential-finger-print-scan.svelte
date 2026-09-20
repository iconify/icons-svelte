<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zof4pzbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zof4pzbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-finger-print-scan" {...props}></Icon>
