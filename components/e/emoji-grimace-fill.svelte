<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9vvp0i8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a9vvp0i8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-grimace-fill" {...props}></Icon>
