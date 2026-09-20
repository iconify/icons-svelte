<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flqx9-u3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flqx9-u3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:audit-report" {...props}></Icon>
