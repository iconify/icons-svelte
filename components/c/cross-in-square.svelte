<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4tk9mluw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e4tk9mluw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cross-in-square" {...props}></Icon>
