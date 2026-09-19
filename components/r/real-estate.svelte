<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c00n87qbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c00n87qbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:real-estate" {...props}></Icon>
