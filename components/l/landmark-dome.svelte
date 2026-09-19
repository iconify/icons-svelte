<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b238y7enx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b238y7enx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:landmark-dome" {...props}></Icon>
