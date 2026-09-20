<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc05_6b-l.css';
import '../../css/m/mn1a8yxak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yc05_6b-l"/><path clip-rule="evenodd" class="mn1a8yxak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:picture-16" {...props}></Icon>
