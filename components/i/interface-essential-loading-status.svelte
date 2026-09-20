<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb6s7laxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tb6s7laxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-status" {...props}></Icon>
