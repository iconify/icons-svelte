<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvk2zxd-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tvk2zxd-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:2fauth" {...props}></Icon>
