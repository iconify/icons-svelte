<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wob3ykb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wob3ykb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pushover-dark" {...props}></Icon>
