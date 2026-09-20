<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia6yr0bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ia6yr0bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openttd-dark" {...props}></Icon>
