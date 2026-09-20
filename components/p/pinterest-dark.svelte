<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_m9zcc1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_m9zcc1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinterest-dark" {...props}></Icon>
