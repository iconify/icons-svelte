<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4hs8gbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a4hs8gbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:folder-compact" {...props}></Icon>
