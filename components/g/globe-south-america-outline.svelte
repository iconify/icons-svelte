<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwlmvlb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qwlmvlb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-south-america-outline" {...props}></Icon>
