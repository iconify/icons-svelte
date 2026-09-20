<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1-2lj-6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t1-2lj-6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:b" {...props}></Icon>
