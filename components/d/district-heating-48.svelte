<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4lrodbjn.css';
import '../../css/s/s3ntjw07u.css';
import '../../css/p/pkgh68sab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l4lrodbjn"/><path class="s3ntjw07u"/><path class="pkgh68sab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-heating-48" {...props}></Icon>
