<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvfm5p4nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jvfm5p4nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:meatballs-v" {...props}></Icon>
