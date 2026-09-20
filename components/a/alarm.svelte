<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8e27lzno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t8e27lzno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:alarm" {...props}></Icon>
