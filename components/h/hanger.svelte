<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayg99-b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayg99-b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:hanger" {...props}></Icon>
