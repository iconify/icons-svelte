<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgquibciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pgquibciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-apple" {...props}></Icon>
