<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s90jwlbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s90jwlbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-eighth-notes" {...props}></Icon>
