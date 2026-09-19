<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1za3mggn.css';
import '../../css/s/s130yc3zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l1za3mggn"/><path class="s130yc3zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-modeler-reference" {...props}></Icon>
