<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_wt6fb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_wt6fb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jwt-io-dark" {...props}></Icon>
