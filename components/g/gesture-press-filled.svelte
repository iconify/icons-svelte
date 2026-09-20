<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq89zwbag.css';
import '../../css/c/cy-trabnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq89zwbag"/><path class="cy-trabnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-press-filled" {...props}></Icon>
