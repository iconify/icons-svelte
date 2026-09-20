<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrke2mbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrke2mbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-robot-dark" {...props}></Icon>
