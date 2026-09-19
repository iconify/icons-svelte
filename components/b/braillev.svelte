<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7ycth5rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="r7ycth5rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillev" {...props}></Icon>
