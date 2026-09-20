<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb6q_6b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tb6q_6b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:diamond" {...props}></Icon>
