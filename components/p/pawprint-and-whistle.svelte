<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvx1k5bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bvx1k5bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pawprint-and-whistle" {...props}></Icon>
