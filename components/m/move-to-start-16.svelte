<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsp875bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jsp875bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-start-16" {...props}></Icon>
