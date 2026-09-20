<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b834icb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b834icb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bricks" {...props}></Icon>
