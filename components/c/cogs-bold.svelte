<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9pe_nrcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":84,"height":80};
const content = `<path clip-rule="evenodd" class="r9pe_nrcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogs-bold" {...props}></Icon>
