<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edgr19bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="edgr19bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:loom" {...props}></Icon>
