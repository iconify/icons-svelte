<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5940d3ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b5940d3ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pencil-ellipsis-rectangle" {...props}></Icon>
