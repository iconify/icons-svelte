<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2pjovc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l2pjovc9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kiss-bold" {...props}></Icon>
