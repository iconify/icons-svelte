<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yefgfcbum.css';
import '../../css/w/wp8j1tmrq.css';
import '../../css/r/rb9owibwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yefgfcbum"/><path class="wp8j1tmrq"/><path class="rb9owibwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-clock-48-bold" {...props}></Icon>
