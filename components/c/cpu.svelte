<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcpbgyiwr.css';
import '../../css/x/x71-5zqyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rcpbgyiwr"/><path class="x71-5zqyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:cpu" {...props}></Icon>
