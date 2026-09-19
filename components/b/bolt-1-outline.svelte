<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/athg_qphj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="athg_qphj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bolt-1-outline" {...props}></Icon>
