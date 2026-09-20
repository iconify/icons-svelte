<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y831veb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y831veb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-boxes-16-solid" {...props}></Icon>
