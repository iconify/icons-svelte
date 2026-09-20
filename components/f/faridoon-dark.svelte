<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj67-z5jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mj67-z5jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:faridoon-dark" {...props}></Icon>
