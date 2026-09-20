<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilikg4vpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilikg4vpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:briefing-light" {...props}></Icon>
