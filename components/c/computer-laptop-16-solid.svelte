<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-2tcckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9-2tcckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-laptop-16-solid" {...props}></Icon>
