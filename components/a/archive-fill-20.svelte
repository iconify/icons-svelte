<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf7tsiqra.css';
import '../../css/e/eugsobcjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zf7tsiqra"/><path class="eugsobcjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:archive-fill-20" {...props}></Icon>
