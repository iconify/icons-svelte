<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3i5l3b6q.css';
import '../../css/t/to0kfkbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3i5l3b6q"/><path class="to0kfkbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-check-20" {...props}></Icon>
