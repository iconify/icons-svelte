<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj66lkljm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tj66lkljm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:p-arrow-down" {...props}></Icon>
