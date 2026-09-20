<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afhl67o8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="afhl67o8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:dog-shelter" {...props}></Icon>
