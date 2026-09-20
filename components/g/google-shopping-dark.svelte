<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blmt__b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blmt__b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-shopping-dark" {...props}></Icon>
