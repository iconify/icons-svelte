<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itn_tacpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itn_tacpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eleventy-dark" {...props}></Icon>
