<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4mhi4b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4mhi4b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-music" {...props}></Icon>
