<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi_9_0blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zi_9_0blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:d-arrow-left" {...props}></Icon>
