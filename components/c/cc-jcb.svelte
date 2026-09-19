<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja3dp1woh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="ja3dp1woh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-jcb" {...props}></Icon>
