<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivu72hdvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ivu72hdvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:robot-head-bold" {...props}></Icon>
