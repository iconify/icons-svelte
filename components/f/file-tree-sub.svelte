<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyac__b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fyac__b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-tree-sub" {...props}></Icon>
