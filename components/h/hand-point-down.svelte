<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkk764efu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qkk764efu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-point-down" {...props}></Icon>
