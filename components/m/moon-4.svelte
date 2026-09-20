<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3jlfq7fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="v3jlfq7fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-4" {...props}></Icon>
