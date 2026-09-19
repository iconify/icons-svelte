<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx1xdecpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fx1xdecpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:envelope-open-heart" {...props}></Icon>
