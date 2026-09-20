<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c48s32eie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c48s32eie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-beside-oval-broadleaved-tree" {...props}></Icon>
