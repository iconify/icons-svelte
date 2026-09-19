<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh210v_jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zh210v_jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-beam-bold" {...props}></Icon>
