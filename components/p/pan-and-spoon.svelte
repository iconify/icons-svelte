<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzoz0rb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dzoz0rb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pan-and-spoon" {...props}></Icon>
