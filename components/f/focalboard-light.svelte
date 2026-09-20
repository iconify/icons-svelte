<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxj88veqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxj88veqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:focalboard-light" {...props}></Icon>
