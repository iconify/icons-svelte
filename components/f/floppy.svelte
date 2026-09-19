<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j26y6ccfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j26y6ccfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:floppy" {...props}></Icon>
