<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avsbps_-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="avsbps_-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:behance" {...props}></Icon>
