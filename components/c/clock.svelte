<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux923mb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ux923mb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:clock" {...props}></Icon>
