<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_wwlb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw_wwlb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moodle-dark" {...props}></Icon>
