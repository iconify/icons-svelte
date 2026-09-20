<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh45i_bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wh45i_bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dalibo-dark" {...props}></Icon>
