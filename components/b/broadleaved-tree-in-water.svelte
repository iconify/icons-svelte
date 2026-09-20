<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy5fcmbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jy5fcmbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:broadleaved-tree-in-water" {...props}></Icon>
