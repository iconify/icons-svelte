<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtrg6izee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vtrg6izee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-right-square-fill" {...props}></Icon>
