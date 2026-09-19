<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h844aq-9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h844aq-9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-right-square" {...props}></Icon>
