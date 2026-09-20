<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_zllg1bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a_zllg1bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:palm-tree" {...props}></Icon>
