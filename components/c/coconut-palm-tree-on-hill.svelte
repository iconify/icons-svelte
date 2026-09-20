<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf7bxabmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wf7bxabmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coconut-palm-tree-on-hill" {...props}></Icon>
