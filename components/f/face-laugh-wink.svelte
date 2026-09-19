<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5p61zb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j5p61zb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-laugh-wink" {...props}></Icon>
