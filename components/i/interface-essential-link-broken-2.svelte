<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdm4r8b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdm4r8b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-link-broken-2" {...props}></Icon>
