<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1k2lkb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path clip-rule="evenodd" class="y1k2lkb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rallly" {...props}></Icon>
