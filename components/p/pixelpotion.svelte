<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-s41boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="j4-s41boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelpotion" {...props}></Icon>
