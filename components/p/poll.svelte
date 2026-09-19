<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjx3lqb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cjx3lqb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:poll" {...props}></Icon>
