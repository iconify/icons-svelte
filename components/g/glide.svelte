<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_uisxbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="o_uisxbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:glide" {...props}></Icon>
