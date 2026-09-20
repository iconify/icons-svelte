<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy0ni9bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gy0ni9bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:code-document-check" {...props}></Icon>
