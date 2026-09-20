<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9lzej0dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b9lzej0dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:building-alt1-11" {...props}></Icon>
