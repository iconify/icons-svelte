<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-vvq8bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e-vvq8bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:chess-queen" {...props}></Icon>
