<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2kq5nbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2kq5nbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:folder-placeholder-rtl" {...props}></Icon>
