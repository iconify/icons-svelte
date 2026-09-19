<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0jr6ob-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w0jr6ob-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:inking-tool" {...props}></Icon>
