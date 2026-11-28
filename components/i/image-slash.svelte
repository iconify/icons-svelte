<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu72g8qcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cu72g8qcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-slash" {...props}></Icon>
