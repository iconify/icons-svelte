<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhzi09bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xhzi09bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-5-story" {...props}></Icon>
