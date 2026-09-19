<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw0g4dbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xw0g4dbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-line-1-outline" {...props}></Icon>
