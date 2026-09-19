<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4wf3lb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a4wf3lb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-style-outline" {...props}></Icon>
