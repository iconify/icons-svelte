<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8kce2a0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m8kce2a0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:force-batch" {...props}></Icon>
