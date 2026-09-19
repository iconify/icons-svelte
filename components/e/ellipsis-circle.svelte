<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3n4y2bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x3n4y2bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:ellipsis-circle" {...props}></Icon>
