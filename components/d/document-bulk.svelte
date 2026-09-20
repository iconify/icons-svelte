<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-8chbcru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-8chbcru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-bulk" {...props}></Icon>
