<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p822d64mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p822d64mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:dependabot" {...props}></Icon>
