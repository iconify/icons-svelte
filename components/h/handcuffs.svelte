<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvl9o-7-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kvl9o-7-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:handcuffs" {...props}></Icon>
