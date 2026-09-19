<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzce-mzfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lzce-mzfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-right" {...props}></Icon>
