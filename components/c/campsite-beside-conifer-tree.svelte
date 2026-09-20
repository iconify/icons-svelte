<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajw4rybce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ajw4rybce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-beside-conifer-tree" {...props}></Icon>
