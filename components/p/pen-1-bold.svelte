<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfcttob0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nfcttob0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-1-bold" {...props}></Icon>
