<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyjp2ln2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xyjp2ln2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coconut-palm-tree" {...props}></Icon>
