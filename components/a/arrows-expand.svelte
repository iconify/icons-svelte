<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3yxvcb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i3yxvcb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows-expand" {...props}></Icon>
