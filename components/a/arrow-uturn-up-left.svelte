<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp8wsbcdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xp8wsbcdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-uturn-up-left" {...props}></Icon>
