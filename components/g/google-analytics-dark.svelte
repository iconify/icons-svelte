<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meazp9b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="meazp9b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-analytics-dark" {...props}></Icon>
