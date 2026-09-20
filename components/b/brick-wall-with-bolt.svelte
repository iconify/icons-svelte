<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2i7cg_sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b2i7cg_sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:brick-wall-with-bolt" {...props}></Icon>
