<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjq7m9irb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjq7m9irb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-robot-light" {...props}></Icon>
