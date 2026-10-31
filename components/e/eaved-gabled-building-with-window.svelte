<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9yenccxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c9yenccxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building-with-window" {...props}></Icon>
