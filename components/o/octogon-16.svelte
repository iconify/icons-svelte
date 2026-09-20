<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4i5-t89q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4i5-t89q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:octogon-16" {...props}></Icon>
