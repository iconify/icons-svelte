<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt6cbni-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qt6cbni-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lowrise-building-beside-lollipop-tree-on-ground" {...props}></Icon>
