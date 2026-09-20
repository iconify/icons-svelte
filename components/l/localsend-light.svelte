<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up1da4b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="up1da4b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:localsend-light" {...props}></Icon>
