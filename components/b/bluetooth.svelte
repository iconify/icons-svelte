<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_8ijoebc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="a_8ijoebc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bluetooth" {...props}></Icon>
