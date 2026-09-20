<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm4js56by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zm4js56by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-beside-conifer-tree" {...props}></Icon>
