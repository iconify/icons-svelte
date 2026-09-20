<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8oafebxf.css';
import '../../css/r/r0ow-hbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8oafebxf"/><path class="r0ow-hbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:folder-add" {...props}></Icon>
