<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgv7ttrgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xgv7ttrgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baseball-bold" {...props}></Icon>
