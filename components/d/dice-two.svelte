<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj5v0cbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bj5v0cbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dice-two" {...props}></Icon>
