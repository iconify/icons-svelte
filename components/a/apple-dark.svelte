<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs_6xacfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rs_6xacfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apple-dark" {...props}></Icon>
