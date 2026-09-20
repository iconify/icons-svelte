<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy6pjk5oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oy6pjk5oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:mushroom" {...props}></Icon>
