<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vupozobcn.css';
import '../../css/z/zhuxdlbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vupozobcn"/><path class="zhuxdlbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:folder-remove" {...props}></Icon>
