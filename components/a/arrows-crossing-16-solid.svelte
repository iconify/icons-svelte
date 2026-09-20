<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyrw1ub6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lyrw1ub6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing-16-solid" {...props}></Icon>
