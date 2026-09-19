<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_61yfbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c_61yfbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-left-fill" {...props}></Icon>
