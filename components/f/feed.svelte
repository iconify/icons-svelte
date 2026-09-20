<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj3g5vbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hj3g5vbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:feed" {...props}></Icon>
