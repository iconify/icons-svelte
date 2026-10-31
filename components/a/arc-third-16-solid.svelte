<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw3i65bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uw3i65bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-16-solid" {...props}></Icon>
