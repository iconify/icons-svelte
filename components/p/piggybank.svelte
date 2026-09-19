<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_xpt-d8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b_xpt-d8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:piggybank" {...props}></Icon>
