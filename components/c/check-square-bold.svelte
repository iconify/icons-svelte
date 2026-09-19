<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqt3tyb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sqt3tyb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-square-bold" {...props}></Icon>
