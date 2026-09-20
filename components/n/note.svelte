<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x517qpbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x517qpbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:note" {...props}></Icon>
