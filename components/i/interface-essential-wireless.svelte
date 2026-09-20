<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7lb11bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s7lb11bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-wireless" {...props}></Icon>
