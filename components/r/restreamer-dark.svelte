<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voj_yiv9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="voj_yiv9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:restreamer-dark" {...props}></Icon>
