<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcn9ecb-z.css';
import '../../css/f/f-7sbkbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dcn9ecb-z"/><path class="f-7sbkbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:interface-usage" {...props}></Icon>
