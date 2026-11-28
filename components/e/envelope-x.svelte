<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p73jpcb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p73jpcb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:envelope-x" {...props}></Icon>
