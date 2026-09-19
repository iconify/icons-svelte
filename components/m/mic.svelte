<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5lbg1shr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j5lbg1shr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:mic" {...props}></Icon>
