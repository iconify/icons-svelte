<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pecbn_bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="pecbn_bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-up-left" {...props}></Icon>
