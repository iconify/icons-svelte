<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8dsq4bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n8dsq4bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:faceplate-container" {...props}></Icon>
