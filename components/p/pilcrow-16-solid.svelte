<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bde7xsbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bde7xsbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pilcrow-16-solid" {...props}></Icon>
