<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqps1fqqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hqps1fqqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-middle-bold" {...props}></Icon>
