<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8tkshbnt.css';
import '../../css/q/q1adlm-oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8tkshbnt"/><path class="q1adlm-oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:music-assistant" {...props}></Icon>
