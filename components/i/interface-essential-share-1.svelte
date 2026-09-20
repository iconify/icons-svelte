<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz6iieisr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kz6iieisr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-share-1" {...props}></Icon>
