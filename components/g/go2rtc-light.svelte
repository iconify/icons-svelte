<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt448_byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kt448_byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:go2rtc-light" {...props}></Icon>
