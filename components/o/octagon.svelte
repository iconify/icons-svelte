<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec73mxbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ec73mxbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:octagon" {...props}></Icon>
