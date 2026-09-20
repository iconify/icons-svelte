<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b82tnpazp.css';
import '../../css/v/v75yc8b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b82tnpazp"/><path class="v75yc8b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:needleleaved-tree-bottom-right-horizontal-line" {...props}></Icon>
