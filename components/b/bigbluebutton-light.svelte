<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxcyibc3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxcyibc3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bigbluebutton-light" {...props}></Icon>
