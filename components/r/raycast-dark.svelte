<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3-wu62s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ar3-wu62s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raycast-dark" {...props}></Icon>
