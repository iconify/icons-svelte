<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0k6kk79s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j0k6kk79s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can" {...props}></Icon>
