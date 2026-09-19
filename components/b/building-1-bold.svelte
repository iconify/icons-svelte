<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqgee5byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cqgee5byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-1-bold" {...props}></Icon>
