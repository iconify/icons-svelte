<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkx3sqbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="bkx3sqbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-25" {...props}></Icon>
