<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-iu0r2yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f-iu0r2yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:picnic-table-bold" {...props}></Icon>
