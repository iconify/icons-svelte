<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncl2nwb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ncl2nwb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anvil-and-mallet" {...props}></Icon>
