<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxa3dwbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxa3dwbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moodist-light" {...props}></Icon>
