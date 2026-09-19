<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cap52ybmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="cap52ybmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:plus" {...props}></Icon>
