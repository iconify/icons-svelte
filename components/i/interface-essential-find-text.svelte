<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaionfb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zaionfb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-find-text" {...props}></Icon>
