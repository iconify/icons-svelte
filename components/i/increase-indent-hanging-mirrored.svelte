<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3dmq6brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h3dmq6brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:increase-indent-hanging-mirrored" {...props}></Icon>
