<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si0jw2byf.css';
import '../../css/r/r7dafkb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="si0jw2byf"/><path class="r7dafkb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bookmarks-sharp" {...props}></Icon>
