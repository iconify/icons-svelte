<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d25h6sbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d25h6sbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2000-dark" {...props}></Icon>
