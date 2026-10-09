<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8jsxg0hb.css';
import '../../css/y/y288-qr4x.css';
import '../../css/z/zzhfcob3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s8jsxg0hb"/><path class="y288-qr4x"/><path class="zzhfcob3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-search-48-bold" {...props}></Icon>
