<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeb5a7bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oeb5a7bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:clipboard-list" {...props}></Icon>
