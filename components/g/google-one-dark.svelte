<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7c9s3b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f7c9s3b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-one-dark" {...props}></Icon>
